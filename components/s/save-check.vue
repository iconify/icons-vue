<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgylmvh5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgylmvh5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:save-check" /></template>
