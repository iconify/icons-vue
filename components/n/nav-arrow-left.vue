<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btetopfwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btetopfwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:nav-arrow-left" /></template>
