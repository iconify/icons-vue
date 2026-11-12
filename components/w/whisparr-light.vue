<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am2cvt6mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="am2cvt6mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:whisparr-light" /></template>
