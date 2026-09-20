<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls-cjjsgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls-cjjsgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rocket-2-linear" /></template>
