<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yily_k3_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yily_k3_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:test" /></template>
