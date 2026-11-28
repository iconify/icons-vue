<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-j3qmbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-j3qmbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tea-cup-heart" /></template>
