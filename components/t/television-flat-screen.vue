<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu11l_tog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="eu11l_tog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:television-flat-screen" /></template>
