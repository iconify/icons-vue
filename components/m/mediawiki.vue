<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6_61xbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x6_61xbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mediawiki" /></template>
