<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5ta4hb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h5ta4hb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:stop-16" /></template>
