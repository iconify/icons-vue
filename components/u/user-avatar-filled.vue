<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkwx1nbmk.css';
import '../../css/a/aq4pnbcei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wkwx1nbmk"/><path class="aq4pnbcei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-avatar-filled" /></template>
