<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-323drdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-323drdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pilcrow-right" /></template>
