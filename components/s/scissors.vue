<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wom6iac3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wom6iac3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:scissors" /></template>
