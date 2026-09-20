<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j48clrlca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j48clrlca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seafile-dark" /></template>
