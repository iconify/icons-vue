<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze7k2gbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze7k2gbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:users-star" /></template>
