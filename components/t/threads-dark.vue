<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gra6c-g-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gra6c-g-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:threads-dark" /></template>
