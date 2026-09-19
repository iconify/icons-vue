<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acb0atomk.css';
import '../../css/g/gb7o9bbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="acb0atomk"/><path class="gb7o9bbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-small-caps" /></template>
