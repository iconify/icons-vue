<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2y9pl2lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-left-outline-rounded" /></template>
<style>
.d2y9pl2lv {
  fill: currentColor;
  d: path("M6.23 20q-.69 0-1.152-.462q-.463-.463-.463-1.153V5.615q0-.69.463-1.152Q5.541 4 6.231 4H9q.69 0 1.153.463t.463 1.153v12.769q0 .69-.463 1.153T9 20zM15 20q-.69 0-1.153-.462t-.462-1.153V5.615q0-.69.462-1.152T15 4h2.77q.69 0 1.152.463q.463.462.463 1.153v12.769q0 .69-.463 1.153Q18.46 20 17.77 20zm3.385-14.385q0-.23-.193-.423T17.77 5H15q-.23 0-.423.192t-.192.423v12.77q0 .23.192.423T15 19h2.77q.23 0 .422-.192t.193-.424z");
}

</style>
