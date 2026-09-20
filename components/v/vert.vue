<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo0p6m5ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bo0p6m5ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vert" /></template>
