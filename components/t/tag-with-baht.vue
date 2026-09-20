<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aawv9vq4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aawv9vq4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tag-with-baht" /></template>
