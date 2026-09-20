<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6c7q-smu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6c7q-smu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skip-remove-outline" /></template>
