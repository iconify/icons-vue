<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydrht2b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ydrht2b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:opensuse" /></template>
