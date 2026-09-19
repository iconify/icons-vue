<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgo2aer-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgo2aer-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-access-for-service-animal-4" /></template>
