<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kybc7u4rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kybc7u4rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unlock-fill" /></template>
