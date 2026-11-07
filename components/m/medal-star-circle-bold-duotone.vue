<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eprh5acmo.css';
import '../../css/x/x0-y109_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eprh5acmo"/><path clip-rule="evenodd" class="x0-y109_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-circle-bold-duotone" /></template>
