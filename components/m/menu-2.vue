<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_n-ew7ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_n-ew7ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:menu-2" /></template>
