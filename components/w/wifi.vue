<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfg0c2bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfg0c2bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:wifi" /></template>
