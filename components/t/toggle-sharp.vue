<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cok6hld-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cok6hld-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:toggle-sharp" /></template>
