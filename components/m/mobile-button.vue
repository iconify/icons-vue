<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeedktbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yeedktbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:mobile-button" /></template>
