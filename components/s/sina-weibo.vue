<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixswl67rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ixswl67rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:sina-weibo" /></template>
