<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbiaezbeq.css';
import '../../css/u/uy-3x3bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbiaezbeq"/><path class="uy-3x3bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:square-circle-24" /></template>
