<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr_ojacek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr_ojacek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play-card-10-filled" /></template>
