<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phkdd0b6a.css';
import '../../css/d/d0bxfnb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phkdd0b6a secondary"/><path class="d0bxfnb3f primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:semicircle-duo" /></template>
