<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr7a41bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr7a41bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stop-bold" /></template>
