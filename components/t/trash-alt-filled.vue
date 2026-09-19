<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr3ppexhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr3ppexhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:trash-alt-filled" /></template>
