<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxd97lx-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxd97lx-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:three-waves-solid" /></template>
