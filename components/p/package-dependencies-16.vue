<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/both_jbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="both_jbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:package-dependencies-16" /></template>
