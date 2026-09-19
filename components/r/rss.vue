<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ift6jxb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ift6jxb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:rss" /></template>
