<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifp3-ac9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifp3-ac9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pilcrow-left" /></template>
