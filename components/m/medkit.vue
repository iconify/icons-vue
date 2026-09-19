<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c94btrm2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c94btrm2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:medkit" /></template>
