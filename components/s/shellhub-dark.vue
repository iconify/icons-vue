<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8z_ivbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e8z_ivbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shellhub-dark" /></template>
