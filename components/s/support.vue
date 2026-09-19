<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-9ibcxgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-9ibcxgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:support" /></template>
