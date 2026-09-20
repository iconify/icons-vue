<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk7_6xv2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lk7_6xv2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-right-outline" /></template>
