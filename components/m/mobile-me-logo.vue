<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-jb5hbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-jb5hbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mobile-me-logo" /></template>
