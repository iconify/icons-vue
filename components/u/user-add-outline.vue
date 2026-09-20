<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxh27cc0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxh27cc0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:user-add-outline" /></template>
