<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0s2u4z6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0s2u4z6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:pizza" /></template>
