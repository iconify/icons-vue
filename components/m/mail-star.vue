<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwpuxgb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwpuxgb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mail-star" /></template>
