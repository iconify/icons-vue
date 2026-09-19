<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm2dxfjpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm2dxfjpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:phone-solid" /></template>
