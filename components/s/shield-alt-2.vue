<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2zodh4mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2zodh4mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shield-alt-2" /></template>
