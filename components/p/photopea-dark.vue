<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojo9uubfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojo9uubfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:photopea-dark" /></template>
