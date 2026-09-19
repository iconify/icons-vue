<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gylx0qgaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gylx0qgaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-vertical-alignment" /></template>
