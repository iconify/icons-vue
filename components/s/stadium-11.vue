<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdg4rh5wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="jdg4rh5wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:stadium-11" /></template>
