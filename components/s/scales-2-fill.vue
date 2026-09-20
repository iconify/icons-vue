<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb8qvqbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb8qvqbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scales-2-fill" /></template>
