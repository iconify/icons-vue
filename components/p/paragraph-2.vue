<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unaz6kbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unaz6kbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:paragraph-2" /></template>
