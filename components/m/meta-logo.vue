<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr53lcc8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr53lcc8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:meta-logo" /></template>
