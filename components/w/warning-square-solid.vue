<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0cg2ushw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p0cg2ushw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:warning-square-solid" /></template>
