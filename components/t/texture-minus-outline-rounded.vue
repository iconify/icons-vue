<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjaz7wbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:texture-minus-outline-rounded" /></template>
<style>
.cjaz7wbvs {
  fill: currentColor;
  d: path("M4.135 19.861q-.14-.137-.153-.338t.164-.377L19.152 4.141q.183-.183.383-.158t.339.161t.153.335t-.167.375L4.848 19.86q-.177.177-.375.158t-.338-.157M14.5 17.616q-.213 0-.356-.144T14 17.115t.144-.356t.356-.144h6q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.144zM4.135 12.68q-.14-.138-.153-.338t.164-.377l7.82-7.82q.176-.177.372-.158q.196.02.335.158t.158.335t-.158.373l-7.825 7.825q-.177.177-.375.158t-.338-.156m13.669 1.404q-.177.177-.373.158q-.196-.02-.335-.158q-.139-.14-.158-.335q-.019-.196.158-.373l2.056-2.056q.177-.177.368-.152t.332.163t.16.332t-.158.37zM4.696 5.65q-.192.192-.444.095Q4 5.65 4 5.377v-.57q0-.342.232-.575T4.808 4h.569q.272 0 .368.252q.097.252-.095.444zm6.612 14.206q-.14-.144-.14-.357t.138-.353t.354-.14t.358.139t.143.354t-.144.358t-.356.143t-.353-.144");
}

</style>
