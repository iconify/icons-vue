<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d25h6sbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d25h6sbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-powerpoint-2000-dark" /></template>
