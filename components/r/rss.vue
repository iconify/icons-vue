<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7n3pkxoe.css';
import '../../css/y/yy8wd3b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7n3pkxoe"/><path class="yy8wd3b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rss" /></template>
