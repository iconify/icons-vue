<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_695xo7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n_695xo7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:volcano" /></template>
