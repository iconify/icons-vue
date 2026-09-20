<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-zzp6bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-zzp6bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:map" /></template>
