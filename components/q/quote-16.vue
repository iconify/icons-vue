<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sofplebhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sofplebhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:quote-16" /></template>
