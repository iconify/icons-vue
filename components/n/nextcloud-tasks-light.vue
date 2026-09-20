<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu1n_0w8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lu1n_0w8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-tasks-light" /></template>
