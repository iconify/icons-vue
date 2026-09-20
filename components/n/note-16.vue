<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b741yrbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b741yrbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:note-16" /></template>
