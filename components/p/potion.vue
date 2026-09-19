<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjwzmm--m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pjwzmm--m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:potion" /></template>
