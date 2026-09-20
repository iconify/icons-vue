<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhmtjdsiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhmtjdsiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:winds-solid" /></template>
