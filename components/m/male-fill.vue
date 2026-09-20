<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1zfbdc2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1zfbdc2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:male-fill" /></template>
