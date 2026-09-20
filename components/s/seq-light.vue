<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m00o5vb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m00o5vb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seq-light" /></template>
