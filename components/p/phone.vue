<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiihi1bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hiihi1bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:phone" /></template>
