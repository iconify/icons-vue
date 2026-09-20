<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufdfntbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ufdfntbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:washing-machine" /></template>
