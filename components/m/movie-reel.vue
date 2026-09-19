<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnerrsv2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wnerrsv2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:movie-reel" /></template>
