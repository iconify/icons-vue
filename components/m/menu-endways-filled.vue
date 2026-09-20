<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c58930t5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c58930t5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:menu-endways-filled" /></template>
