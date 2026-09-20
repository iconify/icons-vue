<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_u_2cbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_u_2cbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:stock-solid" /></template>
