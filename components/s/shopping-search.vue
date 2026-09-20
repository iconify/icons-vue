<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-z_8uu5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-z_8uu5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shopping-search" /></template>
