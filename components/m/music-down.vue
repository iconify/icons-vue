<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz7gnccvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz7gnccvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-down" /></template>
