<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktp1mbiey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ktp1mbiey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-smartphone-outline" /></template>
