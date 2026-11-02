<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt9vprasy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt9vprasy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:maple-leaf-line" /></template>
