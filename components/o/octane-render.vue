<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imx95tuqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imx95tuqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:octane-render" /></template>
