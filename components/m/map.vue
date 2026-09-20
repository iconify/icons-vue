<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md8a7y_mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md8a7y_mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:map" /></template>
