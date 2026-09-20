<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t-8d_je_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ticket-diagonal-20-regular" /></template>
<style>
.t-8d_je_d {
  fill: currentColor;
  d: path("M9.943 2.59a2 2 0 0 1 2.829 0l.907.908c.3.301.265.739.063 1.013a1.25 1.25 0 0 0 1.745 1.746l.11-.068a.78.78 0 0 1 .846.079l.058.052l.917.917c.78.781.781 2.048 0 2.83l-7.353 7.353a2 2 0 0 1-2.829 0l-.917-.917c-.3-.301-.265-.74-.063-1.014l.103-.164a1.25 1.25 0 0 0-1.85-1.582c-.273.202-.712.237-1.013-.063l-.906-.906a2 2 0 0 1 0-2.83zm2.122.708a1 1 0 0 0-1.415 0L8.832 5.115l1.07 1.07a.5.5 0 0 1-.707.708l-1.07-1.07l-4.828 4.828a1 1 0 0 0 0 1.415l.77.77a2.25 2.25 0 0 1 3.096 3.096l.78.781a1 1 0 0 0 1.414 0l4.83-4.83l-1.078-1.076a.5.5 0 0 1 .707-.707l1.078 1.077l1.817-1.818c.39-.39.39-1.024 0-1.415l-.781-.78a2.23 2.23 0 0 1-1.18.336a2.25 2.25 0 0 1-1.915-3.432zM10.609 7.6a.5.5 0 0 1 .707 0l1.086 1.086a.5.5 0 0 1-.707.707L10.61 8.307a.5.5 0 0 1 0-.707");
}

</style>
