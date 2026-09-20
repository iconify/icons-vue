<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnvmww__d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnvmww__d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pronounsdotpage" /></template>
