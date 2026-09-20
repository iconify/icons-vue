<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be2tj8b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be2tj8b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tree-outline" /></template>
