<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezce_6bqy.css';
import '../../css/x/xtew6gkwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ezce_6bqy"/><path class="xtew6gkwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:stumbleupon" /></template>
