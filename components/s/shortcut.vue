<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz17t_8qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="tz17t_8qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:shortcut" /></template>
