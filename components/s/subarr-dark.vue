<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or85ekbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="or85ekbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:subarr-dark" /></template>
