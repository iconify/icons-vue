<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiijosb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iiijosb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-speaking-to-amphitheater" /></template>
