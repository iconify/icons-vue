<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_oqwdk7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b_oqwdk7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:speech-bubble-exclamation" /></template>
