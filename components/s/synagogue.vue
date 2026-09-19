<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/belwusvjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="belwusvjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:synagogue" /></template>
