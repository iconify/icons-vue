<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh3zz6b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh3zz6b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:text-align-left" /></template>
