<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzv4o8oal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tzv4o8oal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:x-mark-solid" /></template>
