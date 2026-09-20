<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb9885b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="hb9885b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sign-in" /></template>
