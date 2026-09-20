<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxnf1q5gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lxnf1q5gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:sort-filled" /></template>
