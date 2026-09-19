<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do1g0fkgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="do1g0fkgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:microsoft-word" /></template>
