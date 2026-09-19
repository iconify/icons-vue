<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crjayq9qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crjayq9qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:menu" /></template>
