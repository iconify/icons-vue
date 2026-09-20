<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9qxqov1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p9qxqov1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tasks" /></template>
