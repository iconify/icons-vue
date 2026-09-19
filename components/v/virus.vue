<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjqdimbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjqdimbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:virus" /></template>
