<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkdrb0b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="qkdrb0b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:mobileme" /></template>
