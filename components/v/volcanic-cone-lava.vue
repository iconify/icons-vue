<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6f7jkmro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o6f7jkmro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:volcanic-cone-lava" /></template>
