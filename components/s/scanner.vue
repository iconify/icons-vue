<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv3b-bb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv3b-bb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:scanner" /></template>
