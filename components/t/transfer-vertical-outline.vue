<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y73vvr34y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y73vvr34y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transfer-vertical-outline" /></template>
