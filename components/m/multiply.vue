<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmu4csbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmu4csbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:multiply" /></template>
