<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti86nvoen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ti86nvoen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seq-dark" /></template>
