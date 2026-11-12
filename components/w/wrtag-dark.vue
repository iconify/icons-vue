<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szaw_2tpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="szaw_2tpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wrtag-dark" /></template>
