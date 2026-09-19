<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mglnvccod.css';
import '../../css/x/xzv0t0boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mglnvccod"/><path class="xzv0t0boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:window-close" /></template>
