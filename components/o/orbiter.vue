<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iytq7umhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iytq7umhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:orbiter" /></template>
