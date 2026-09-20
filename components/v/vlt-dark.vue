<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok9hfbanf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":175};
const content = `<path class="ok9hfbanf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vlt-dark" /></template>
