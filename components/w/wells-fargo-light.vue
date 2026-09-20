<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8yf87b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g8yf87b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wells-fargo-light" /></template>
