<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw_cjjfhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw_cjjfhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:omega" /></template>
