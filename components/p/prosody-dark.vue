<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-352jb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v-352jb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prosody-dark" /></template>
