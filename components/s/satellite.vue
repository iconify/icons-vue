<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-n5_6z9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-n5_6z9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:satellite" /></template>
