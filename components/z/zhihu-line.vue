<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9yk69bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9yk69bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:zhihu-line" /></template>
