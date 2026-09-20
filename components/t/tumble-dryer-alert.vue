<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufzg5m6eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufzg5m6eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tumble-dryer-alert" /></template>
