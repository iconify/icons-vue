<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avhybemoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="avhybemoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:youtube-dl-dark" /></template>
