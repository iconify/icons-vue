<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erigzxhwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reset-colors-outline" /></template>
<style>
.erigzxhwe {
  fill: currentColor;
  d: path("M16.912 21.936q-.18-.065-.327-.213l-3.789-3.788q-.296-.29-.296-.685t.296-.69l3.766-3.76l-1.835-1.834l.689-.708l6.332 6.302q.148.148.213.327q.064.179.064.357t-.064.36q-.065.183-.213.33l-3.788 3.789q-.148.148-.33.213q-.182.064-.36.064t-.359-.065M13.7 17.04h7.08l-3.53-3.531zM5 20v-1h3.312q-1.916-1-3.114-2.851T4 12q0-1.664.626-3.118T6.34 6.34t2.542-1.714T12 4q2.706 0 4.778 1.584q2.072 1.583 2.843 4.032h-1.036q-.727-2.027-2.504-3.322T12 5Q9.075 5 7.038 7.038T5 12q0 2.108 1.11 3.79Q7.222 17.474 9 18.309V15h1v5z");
}

</style>
