<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1kzwfi4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n1kzwfi4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unwrap-16" /></template>
