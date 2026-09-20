<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mehrf5bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mehrf5bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:upload-line" /></template>
