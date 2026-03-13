<script setup>
import '@carbon/web-components/es/components/checkbox/checkbox.js';
</script>

<template>
  <main>
    <cds-checkbox helper-text="Helper text goes here">Checkbox label</cds-checkbox>
    <br><br>
    <cds-checkbox invalid="" invalid-text="Invalid test goes here">Checkbox label</cds-checkbox>
    <br><br>
    <cds-checkbox warn="" warn-text="Warning test goes here">Checkbox label</cds-checkbox>
    <br><br>
    <cds-checkbox readonly="">Checkbox label</cds-checkbox>
  </main>
</template>

