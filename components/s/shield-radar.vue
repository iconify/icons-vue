<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ram-k2m3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-radar" /></template>
<style>
.ram-k2m3v {
  fill: currentColor;
  d: path("M17 22q-2.083 0-3.542-1.457T12 17.005t1.457-3.543T16.996 12t3.543 1.458T22 17q0 .391-.061.749t-.166.684q-.012-.018-.026-.035t-.031-.034l-.76-.785q.025-.145.034-.29T21 17q0-1.65-1.175-2.825T17 13t-2.825 1.175T13 17t1.175 2.825T17 21q.144 0 .29-.01q.144-.01.289-.034l.765.779l.035.034q.017.018.034.029q-.332.108-.681.155T17 22m3.589-1.412q-.166.166-.357.166t-.357-.166l-2.311-2.317q-.081.044-.564.133q-.579 0-.991-.412q-.413-.411-.413-.989t.412-.993t.989-.414t.993.413t.414.991q0 .08-.133.564l2.317 2.317q.166.165.166.354t-.166.354M5 11.1V5.692l7-2.615l7 2.615v4.216q-.494-.14-.99-.217q-.497-.076-1.01-.076q-3.08 0-5.233 2.152Q9.616 13.92 9.616 17q0 .872.193 1.706t.593 1.598q-2.396-1.267-3.899-3.746T5 11.1");
}

</style>
