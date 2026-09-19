<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_i7odbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1026};
const content = `<path class="f_i7odbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:marvin" /></template>
