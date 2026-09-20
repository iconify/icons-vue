<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zror_sbrn.css';
import '../../css/c/c_5bp2b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zror_sbrn"/><path class="c_5bp2b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:person-cursor-16" /></template>
