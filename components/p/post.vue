<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6jrctivg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l6jrctivg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:post" /></template>
