<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6o7nlbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c6o7nlbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-google-outline" /></template>
