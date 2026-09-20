<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmfj0ubqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qmfj0ubqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-properties-outline" /></template>
