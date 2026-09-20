<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8ctmibxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b8ctmibxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:note-solid" /></template>
