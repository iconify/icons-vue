<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyz7sxb6l.css';
import '../../css/o/os103abfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yyz7sxb6l"/><path class="os103abfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:volume-off-stroke-20" /></template>
