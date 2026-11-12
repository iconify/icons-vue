<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cml5n7irm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cml5n7irm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twake-drive-dark" /></template>
