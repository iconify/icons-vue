<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnmlxpzoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qnmlxpzoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:sit-up" /></template>
