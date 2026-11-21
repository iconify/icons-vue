<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmtassnnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dmtassnnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:relaticle-dark" /></template>
