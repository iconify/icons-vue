<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juzkhrbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="juzkhrbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:two-giraffes-on-zoo-uppercase" /></template>
