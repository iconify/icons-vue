<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpcy9wkno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpcy9wkno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:remove-alert-clock-solid" /></template>
