<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfe-jnboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfe-jnboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shield-exclamation" /></template>
