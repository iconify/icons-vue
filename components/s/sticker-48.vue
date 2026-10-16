<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb70seb8t.css';
import '../../css/v/vt3q5aclv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eb70seb8t"/><path class="vt3q5aclv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sticker-48" /></template>
