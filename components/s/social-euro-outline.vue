<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxem6hx9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oxem6hx9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-euro-outline" /></template>
