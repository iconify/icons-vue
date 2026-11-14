<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cywajr2te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:self-review" /></template>
<style>
.cywajr2te {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 8.75q-.001-3.091 2.029-5.284Q9.083 1.248 12 1.248t4.971 2.218Q19.001 5.66 19 8.75q.001 3.09-2.029 5.284q-1.346 1.453-3.062 1.955q.091.335.091.761v3.5q0 2-2 2t-2-2v-3.5q0-.426.091-.761q-1.716-.502-3.062-1.955Q4.999 11.841 5 8.75m8.13-2.528q-.32-.744-1.13-.744t-1.13.744l-.087.203q-.176.407-.618.448l-.219.021q-.807.073-1.058.844q-.251.772.357 1.305l.167.147q.333.293.236.727l-.047.213q-.18.79.475 1.267t1.352.063l.19-.113q.382-.226.762-.001l.192.114q.697.413 1.352-.063q.655-.477.476-1.263l-.048-.218q-.097-.433.236-.726l.165-.146q.61-.534.359-1.306q-.251-.771-1.055-.844l-.222-.021q-.442-.041-.617-.446z");
}

</style>
