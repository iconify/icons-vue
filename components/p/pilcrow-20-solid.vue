<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdt-y-bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tdt-y-bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pilcrow-20-solid" /></template>
