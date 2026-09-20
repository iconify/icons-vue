<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjn9f7o-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gjn9f7o-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:reply-16" /></template>
