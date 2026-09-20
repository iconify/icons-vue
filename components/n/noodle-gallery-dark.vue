<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3nqpne1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g3nqpne1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:noodle-gallery-dark" /></template>
