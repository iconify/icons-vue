<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glx4dwbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glx4dwbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:text-direction-rtl" /></template>
