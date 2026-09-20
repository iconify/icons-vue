<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjcdnt86x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjcdnt86x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:usaa-dark" /></template>
