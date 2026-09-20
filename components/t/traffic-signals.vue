<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9lkkjbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q9lkkjbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:traffic-signals" /></template>
