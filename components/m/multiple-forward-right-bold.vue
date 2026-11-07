<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkvbobd_g.css';
import '../../css/p/pfr06xbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkvbobd_g"/><path clip-rule="evenodd" class="pfr06xbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:multiple-forward-right-bold" /></template>
