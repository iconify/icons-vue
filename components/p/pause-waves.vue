<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki9nf03-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki9nf03-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pause-waves" /></template>
