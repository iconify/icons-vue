<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzoz0rb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dzoz0rb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:pan-and-spoon" /></template>
