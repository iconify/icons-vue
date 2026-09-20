<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3i_9n3oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3i_9n3oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:weibo-fill" /></template>
