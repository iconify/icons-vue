<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkoaw5bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkoaw5bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mastodon-fill-round" /></template>
