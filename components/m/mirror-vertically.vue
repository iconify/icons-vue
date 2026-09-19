<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2-glub9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j2-glub9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:mirror-vertically" /></template>
