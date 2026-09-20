<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me2zngofg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="me2zngofg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unregistry-dark" /></template>
