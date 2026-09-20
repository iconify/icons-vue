<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2t18pbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2t18pbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-down-sharp" /></template>
