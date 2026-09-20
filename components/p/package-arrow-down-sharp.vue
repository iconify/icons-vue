<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpk53t-ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpk53t-ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-arrow-down-sharp" /></template>
