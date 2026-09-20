<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd_h-2b1r.css';
import '../../css/b/bbae6rbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd_h-2b1r"/><path class="bbae6rbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rss-2-line" /></template>
