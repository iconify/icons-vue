<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq_btub1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq_btub1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:trowel" /></template>
