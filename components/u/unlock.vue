<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7tbccbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="u7tbccbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:unlock" /></template>
