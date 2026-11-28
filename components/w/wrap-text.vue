<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc28web6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc28web6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wrap-text" /></template>
