<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_irnx67r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_irnx67r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:prohibited" /></template>
