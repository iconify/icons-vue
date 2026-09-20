<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq3a1xbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fq3a1xbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oikos-dark" /></template>
