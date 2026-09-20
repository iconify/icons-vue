<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxucj6f8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxucj6f8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tornado-line" /></template>
