<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc9kp24_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc9kp24_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:replace-all" /></template>
