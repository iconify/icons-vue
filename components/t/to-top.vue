<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in5ftwbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="in5ftwbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:to-top" /></template>
