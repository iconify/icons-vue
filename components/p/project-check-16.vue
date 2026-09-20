<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgje56boo.css';
import '../../css/y/ymxiy1_5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zgje56boo"/><path class="ymxiy1_5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:project-check-16" /></template>
