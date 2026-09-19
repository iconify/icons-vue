<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axc5g2bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="axc5g2bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:swimmer" /></template>
