<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seu7efbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="seu7efbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raycast" /></template>
