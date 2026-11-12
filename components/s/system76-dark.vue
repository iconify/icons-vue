<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyqg1bbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vyqg1bbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:system76-dark" /></template>
