<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtr7kdoiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:snow-mountain-top" /></template>
<style>
.wtr7kdoiz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.002 8.939L3.36 17.003q-.72 1.25.003 2.499q.722 1.248 2.164 1.248h12.946q1.442 0 2.164-1.248q.723-1.249.003-2.499l-4.642-8.064q.011.141-.029.275q-.041.135-.127.246l-1.75 2.25q-.029.037-.062.07q-.105.106-.243.163T13.5 12t-.287-.057t-.243-.163l-.97-.969l-.97.969q-.033.033-.07.062q-.058.045-.124.078q-.066.034-.137.053q-.071.02-.145.025t-.147-.004t-.143-.032t-.135-.06t-.12-.085t-.101-.107l-1.75-2.25q-.086-.111-.127-.246q-.04-.134-.029-.275m.32-.555q.059-.041.124-.07t.135-.045t.14-.018q.072-.003.142.008q.071.01.138.034t.129.06t.115.083t.097.104l1.228 1.579l.9-.899q.105-.106.243-.163T12 9t.287.057t.243.163l.9.899l1.228-1.579q.044-.057.097-.104t.115-.083t.129-.06t.138-.034t.142-.008t.14.018t.135.045t.124.07L14.167 5.76Q13.446 4.506 12 4.506T9.833 5.76z");
}

</style>
