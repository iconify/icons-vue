<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iffe5zl0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iffe5zl0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:maya-pyramids-line" /></template>
