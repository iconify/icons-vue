<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze_ex8o5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ze_ex8o5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-letter-boxed-dark" /></template>
