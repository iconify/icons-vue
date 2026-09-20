<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z53j1gsut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z53j1gsut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:progressive-dark" /></template>
