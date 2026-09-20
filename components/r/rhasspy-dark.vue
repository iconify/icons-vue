<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlm1inbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vlm1inbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rhasspy-dark" /></template>
