<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kge1oi_wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kge1oi_wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:thumb-down-off" /></template>
