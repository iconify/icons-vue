<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zobiihb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zobiihb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-outline" /></template>
