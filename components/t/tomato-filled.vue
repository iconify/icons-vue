<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/posi6w9sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="posi6w9sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tomato-filled" /></template>
