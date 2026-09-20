<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gapcm6cdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gapcm6cdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mood-look-right" /></template>
