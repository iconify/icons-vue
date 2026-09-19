<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owxqd0bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="owxqd0bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:speaker-low" /></template>
