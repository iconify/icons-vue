<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckcrm-l0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckcrm-l0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-in-down-right-sharp" /></template>
