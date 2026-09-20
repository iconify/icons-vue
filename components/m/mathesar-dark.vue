<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efxus0nfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="efxus0nfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mathesar-dark" /></template>
