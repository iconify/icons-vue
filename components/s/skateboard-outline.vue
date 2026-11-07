<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km5m1bcov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="km5m1bcov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skateboard-outline" /></template>
