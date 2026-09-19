<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvunr3b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lvunr3b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:paperclip-16" /></template>
