<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-lsa2wrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-lsa2wrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:restore-backup" /></template>
