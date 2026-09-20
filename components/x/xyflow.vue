<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njonlebmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njonlebmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:xyflow" /></template>
