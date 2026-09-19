<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1lmu7b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c1lmu7b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-hook-arrow-small" /></template>
