<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj1rpu33a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jj1rpu33a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typemill-light" /></template>
