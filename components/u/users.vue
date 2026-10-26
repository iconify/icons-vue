<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdyzhebfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cdyzhebfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:users" /></template>
