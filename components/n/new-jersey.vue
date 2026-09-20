<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtrkdubov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xtrkdubov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:new-jersey" /></template>
