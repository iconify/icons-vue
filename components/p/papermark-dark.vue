<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg8z4pjgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kg8z4pjgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermark-dark" /></template>
