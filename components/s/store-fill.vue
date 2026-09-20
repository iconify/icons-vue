<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbb__8bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbb__8bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:store-fill" /></template>
