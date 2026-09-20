<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szxpzob-w.css';
import '../../css/n/nhk3unbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="szxpzob-w"/><path class="nhk3unbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:user-man-love" /></template>
