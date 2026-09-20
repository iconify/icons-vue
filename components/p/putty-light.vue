<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-zny-e6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-zny-e6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:putty-light" /></template>
