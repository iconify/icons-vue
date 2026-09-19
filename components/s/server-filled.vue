<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfsjlsk4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfsjlsk4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:server-filled" /></template>
