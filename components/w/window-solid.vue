<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjgqchbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qjgqchbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:window-solid" /></template>
