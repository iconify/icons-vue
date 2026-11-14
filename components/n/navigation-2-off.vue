<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqcaqub-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqcaqub-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:navigation-2-off" /></template>
