<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7defpb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7defpb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:subtract-circle-bold" /></template>
