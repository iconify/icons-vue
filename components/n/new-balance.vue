<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbgqee1_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbgqee1_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:new-balance" /></template>
