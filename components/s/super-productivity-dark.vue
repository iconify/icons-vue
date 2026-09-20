<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0zk18b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z0zk18b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:super-productivity-dark" /></template>
