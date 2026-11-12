<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie4m0gn1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ie4m0gn1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wavelog-dark" /></template>
