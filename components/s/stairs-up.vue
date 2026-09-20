<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9_dlebfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9_dlebfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:stairs-up" /></template>
