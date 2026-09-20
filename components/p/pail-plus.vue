<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eegmwoa2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eegmwoa2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pail-plus" /></template>
