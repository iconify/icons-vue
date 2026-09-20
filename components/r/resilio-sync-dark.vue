<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6_c0xb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h6_c0xb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:resilio-sync-dark" /></template>
