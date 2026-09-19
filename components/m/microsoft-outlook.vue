<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bak9dbcyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":507,"height":512};
const content = `<path class="bak9dbcyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:microsoft-outlook" /></template>
