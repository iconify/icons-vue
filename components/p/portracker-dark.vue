<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0lvo7bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z0lvo7bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portracker-dark" /></template>
