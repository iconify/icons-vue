<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iihrjxbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":684,"height":1568};
const content = `<path class="iihrjxbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ralph-lauren" /></template>
