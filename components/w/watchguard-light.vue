<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unn_8xtas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unn_8xtas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:watchguard-light" /></template>
