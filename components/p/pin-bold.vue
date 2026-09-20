<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irkc8bc8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irkc8bc8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pin-bold" /></template>
