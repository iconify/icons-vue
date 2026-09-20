<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwwgz8biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qwwgz8biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:vimeo-logo-block" /></template>
