<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz6zjacrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cz6zjacrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:weibo-logo" /></template>
