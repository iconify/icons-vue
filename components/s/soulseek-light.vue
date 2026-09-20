<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya0hl4bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ya0hl4bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:soulseek-light" /></template>
