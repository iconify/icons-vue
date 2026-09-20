<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5rsijhuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g5rsijhuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:windows-close-16" /></template>
