<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkh1ubbwh.css';
import '../../css/n/nzqt12bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lkh1ubbwh"/><path clip-rule="evenodd" class="nzqt12bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:scanner-16" /></template>
