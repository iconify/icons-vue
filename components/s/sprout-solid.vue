<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d97_1ubgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d97_1ubgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sprout-solid" /></template>
