<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yynfaacui.css';
import '../../css/t/tqme7yb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yynfaacui"/><path class="tqme7yb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:question-mark-circle-stroke-20" /></template>
