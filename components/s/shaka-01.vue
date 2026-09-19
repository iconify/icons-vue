<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyqja-u_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyqja-u_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shaka-01" /></template>
