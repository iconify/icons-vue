<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq41bwuze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq41bwuze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-vertical-fill" /></template>
