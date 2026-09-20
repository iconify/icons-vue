<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvdhn8bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lvdhn8bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windows-defender-2016-light" /></template>
