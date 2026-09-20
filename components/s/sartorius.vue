<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxxuin_1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxxuin_1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sartorius" /></template>
