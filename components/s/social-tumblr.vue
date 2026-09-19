<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pchasnb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="pchasnb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-tumblr" /></template>
