<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k23dc3bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k23dc3bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shark-fin-outline" /></template>
