<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il83t9b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="il83t9b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-folder-open" /></template>
