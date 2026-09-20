<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzl_o7baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzl_o7baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sofa-solid" /></template>
