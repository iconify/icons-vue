<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4h25zd1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4h25zd1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:triangle-down-fill" /></template>
