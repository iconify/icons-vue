<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbytv9biz.css';
import '../../css/i/ifxacxt9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dbytv9biz"/><path class="ifxacxt9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-48-bold" /></template>
