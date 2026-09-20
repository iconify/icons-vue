<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af6obb6it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af6obb6it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:more2-filled" /></template>
