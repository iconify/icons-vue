<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-unv1bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:seek-shade" /></template>
<style>
.i-unv1bbb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 11q.001-3.65 2.889-6.216Q7.988 2.253 12 2.253t6.861 2.531Q21.749 7.35 21.75 11q0 .074-.014.146t-.043.141q-.028.068-.069.129q-.041.062-.093.114q-.053.052-.114.093q-.061.042-.13.07q-.068.028-.14.043T21 11.75q-.177 0-.335-.079q-2.665-1.332-5.33 0q-.078.039-.163.059t-.172.02t-.172-.02t-.163-.059q-.958-.479-1.915-.614v6.7q6 .122 6 2.243q0 2.25-6.75 2.25T5.25 20q0-2.121 6-2.243v-6.7q-.957.135-1.915.614q-.078.039-.163.059T9 11.75t-.172-.02t-.163-.059q-2.665-1.332-5.33 0q-.066.033-.137.052q-.071.02-.145.025t-.147-.004t-.143-.032t-.134-.06t-.12-.085t-.101-.107t-.079-.125Q2.25 11.177 2.25 11");
}

</style>
