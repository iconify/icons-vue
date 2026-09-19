<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5lyd3h6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u5lyd3h6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:test-perl" /></template>
