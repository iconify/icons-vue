<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qth9flppj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qth9flppj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:scroll-up" /></template>
