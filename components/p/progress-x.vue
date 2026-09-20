<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmqei6bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmqei6bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:progress-x" /></template>
