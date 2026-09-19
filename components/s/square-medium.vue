<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo-nkybxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jo-nkybxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:square-medium" /></template>
