<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2fqawb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2fqawb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-2-outline" /></template>
