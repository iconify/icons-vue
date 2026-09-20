<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgi_pg35v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgi_pg35v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:power-off-sharp" /></template>
