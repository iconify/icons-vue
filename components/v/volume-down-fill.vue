<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g871mkbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g871mkbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:volume-down-fill" /></template>
