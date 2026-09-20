<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy59z_kqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy59z_kqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rewind-waves-solid" /></template>
