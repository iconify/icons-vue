<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppbqog3mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ppbqog3mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-office-light" /></template>
