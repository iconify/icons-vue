<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzve063hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nzve063hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:snapchat-outline" /></template>
