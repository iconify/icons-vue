<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt1e66bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt1e66bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pen-plus" /></template>
