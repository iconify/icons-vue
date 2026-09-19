<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzbn288cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gzbn288cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:note-double" /></template>
