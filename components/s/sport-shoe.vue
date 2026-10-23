<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk3my9agl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk3my9agl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sport-shoe" /></template>
