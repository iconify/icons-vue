<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmmki2bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmmki2bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:volume-zero-fill" /></template>
