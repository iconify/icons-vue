<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nln509zzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nln509zzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:speedtest-tracker-dark" /></template>
