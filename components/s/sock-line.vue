<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyvovxt3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyvovxt3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sock-line" /></template>
