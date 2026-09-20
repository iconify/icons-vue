<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azmswkban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azmswkban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:xbox-line" /></template>
