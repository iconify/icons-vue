<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-hfxc10a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-hfxc10a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:progress-arc-fill" /></template>
