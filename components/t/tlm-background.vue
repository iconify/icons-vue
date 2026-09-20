<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="iwyt-zlsc"/><path clip-rule="evenodd" class="f8s9wrbdy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tlm-background" /></template>
<style>
.f8s9wrbdy {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m10.013 6.776l1.067-2.197a1.02 1.02 0 0 1 1.84 0l1.067 2.197C13.609 7.8 12.862 8.499 12.002 8.5H12c-.861 0-1.61-.699-1.987-1.724m-.407.836l-.914 1.88a6 6 0 0 1 1.73-.782a3.8 3.8 0 0 1-.816-1.098M6.02 14.993l-.74 1.522a2.5 2.5 0 0 1 1.289.538a6 6 0 0 1-.55-2.06M6.732 20H4.684a.69.69 0 0 1-.613-.995L5.044 17a1.998 1.998 0 0 1 1.688 3m.56 0h2.306a6 6 0 0 1-2.176-1.621c.138.54.092 1.11-.13 1.621m7.11 0h1.806A2.5 2.5 0 0 1 16 18.972A6 6 0 0 1 14.402 20m4.582-2.941l.945 1.945a.69.69 0 0 1-.613.996h-2.549a1.99 1.99 0 0 1-.155-1.662q.34-.408.605-.873a2 2 0 0 1 1.767-.406m-.268-.55l-.736-1.516a6 6 0 0 1-.384 1.675c.356-.138.74-.192 1.12-.159m-3.409-7.016a6 6 0 0 0-1.729-.783c.319-.29.596-.662.816-1.098zM12.5 19.475a5 5 0 0 1-1 0V12H7.669q.317-.548.76-1h7.141q.444.452.761 1H12.5zm.5-.075a5.002 5.002 0 0 0 3.584-6.9H13zm-1-9.9c1.126 0 2.165.372 3 1H9a4.98 4.98 0 0 1 3-1m-4.584 3A5.002 5.002 0 0 0 11 19.4v-6.9z");
}

.ft5dv1b6b {
  fill: none;
}

.iwyt-zlsc {
  fill: var(--svg-color--eacb7d, #eacb7d);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
