<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow0e6s8yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow0e6s8yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:passbolt-dark" /></template>
