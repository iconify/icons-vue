<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra8bklu7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ra8bklu7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:note-sticky" /></template>
