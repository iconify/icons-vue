<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6onu0rsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p6onu0rsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:siyuan-dark" /></template>
