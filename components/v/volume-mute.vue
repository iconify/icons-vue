<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avl6-q8xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="avl6-q8xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:volume-mute" /></template>
