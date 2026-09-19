<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffcdkmbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ffcdkmbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-wordpress-outline" /></template>
