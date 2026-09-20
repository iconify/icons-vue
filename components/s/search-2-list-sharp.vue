<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy715yv2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy715yv2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-list-sharp" /></template>
