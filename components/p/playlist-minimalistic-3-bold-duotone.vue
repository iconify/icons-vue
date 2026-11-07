<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8b_cacmv.css';
import '../../css/h/hdwbqmb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k8b_cacmv"/><path class="hdwbqmb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-3-bold-duotone" /></template>
