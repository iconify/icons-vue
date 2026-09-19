<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4n9_hbzl.css';
import '../../css/d/dy7t98bks.css';
import '../../css/e/e92ev1b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q4n9_hbzl"/><path class="dy7t98bks"/><path class="e92ev1b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:study-unread" /></template>
