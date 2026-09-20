<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rusgjrbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rusgjrbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-horizontal-sharp" /></template>
