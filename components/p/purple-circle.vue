<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bniecgb9n.css';
import '../../css/s/snpiwsb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="bniecgb9n"/><circle class="snpiwsb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:purple-circle" /></template>
