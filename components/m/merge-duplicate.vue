<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh5ar3jyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oh5ar3jyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:merge-duplicate" /></template>
