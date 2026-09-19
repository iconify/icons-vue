<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnvrhabhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnvrhabhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:uppercase" /></template>
