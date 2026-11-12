<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3f903brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3f903brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nocobase" /></template>
