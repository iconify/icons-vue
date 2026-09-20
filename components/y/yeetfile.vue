<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcr9c3bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lcr9c3bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yeetfile" /></template>
