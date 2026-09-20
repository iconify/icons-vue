<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2c5jrb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2c5jrb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:playlist-add" /></template>
