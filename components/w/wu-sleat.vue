<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_-leybfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="a_-leybfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wu-sleat" /></template>
