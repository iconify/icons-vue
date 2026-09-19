<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7-1w7biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="o7-1w7biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:phabricator" /></template>
