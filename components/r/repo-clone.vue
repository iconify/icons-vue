<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvtem461l.css';
import '../../css/t/tcz9p2b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vvtem461l"/><path class="tcz9p2b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-clone" /></template>
