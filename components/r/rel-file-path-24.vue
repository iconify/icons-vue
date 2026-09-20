<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc91xfboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc91xfboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:rel-file-path-24" /></template>
