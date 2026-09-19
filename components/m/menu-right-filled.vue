<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp95aoe_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp95aoe_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:menu-right-filled" /></template>
