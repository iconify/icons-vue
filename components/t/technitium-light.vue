<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np9k7qb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="np9k7qb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:technitium-light" /></template>
