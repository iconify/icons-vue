<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz84-znwv.css';
import '../../css/l/lxe7e-j4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz84-znwv"/><path class="lxe7e-j4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:play-circle-stroke-add-filled" /></template>
