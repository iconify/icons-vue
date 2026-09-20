<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muo88zbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="muo88zbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seagate-light" /></template>
