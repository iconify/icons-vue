<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yttk-xbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yttk-xbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:minus-16" /></template>
