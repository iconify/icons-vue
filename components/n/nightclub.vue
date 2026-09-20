<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enw5fd1wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="enw5fd1wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:nightclub" /></template>
