<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc3p1bcrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc3p1bcrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pills" /></template>
