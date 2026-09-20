<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqyamvt_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqyamvt_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:user-delete-outline" /></template>
