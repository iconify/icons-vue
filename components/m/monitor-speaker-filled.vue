<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxwu0fb2r.css';
import '../../css/i/i11fypbyz.css';
import '../../css/z/zz61lgz8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxwu0fb2r"/><path clip-rule="evenodd" class="i11fypbyz"/><path class="zz61lgz8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-speaker-filled" /></template>
