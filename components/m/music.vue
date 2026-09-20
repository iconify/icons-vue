<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok4r3opti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ok4r3opti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:music" /></template>
