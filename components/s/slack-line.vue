<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9zntdblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9zntdblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:slack-line" /></template>
