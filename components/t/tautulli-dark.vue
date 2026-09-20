<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3yxxqa6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w3yxxqa6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tautulli-dark" /></template>
