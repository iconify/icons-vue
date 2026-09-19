<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfqul596w.css';
import '../../css/a/ao5bk4bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wfqul596w"/><path class="ao5bk4bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:update-now" /></template>
