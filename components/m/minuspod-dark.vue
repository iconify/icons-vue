<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c85z90qgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c85z90qgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minuspod-dark" /></template>
