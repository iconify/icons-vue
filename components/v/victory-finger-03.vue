<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljx7t8mtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljx7t8mtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:victory-finger-03" /></template>
