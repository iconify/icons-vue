<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st7sd8ykf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st7sd8ykf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:moon-bold" /></template>
