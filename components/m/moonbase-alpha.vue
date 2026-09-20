<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkfr-acjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkfr-acjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:moonbase-alpha" /></template>
