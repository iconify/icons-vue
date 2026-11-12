<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2a_cniwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l2a_cniwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-tables-light" /></template>
