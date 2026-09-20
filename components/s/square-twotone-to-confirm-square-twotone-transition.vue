<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6sxug.css';
import '../../css/i/iw1iew.css';
import '../../css/f/fce2zc.css';
import '../../css/s/so-from-14.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6sxug iw1iew"/><path class="fce2zc iw1iew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:square-twotone-to-confirm-square-twotone-transition" /></template>
