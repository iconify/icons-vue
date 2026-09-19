<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeftv-f_s.css';
import '../../css/w/wwi7ougfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeftv-f_s"/><path class="wwi7ougfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:owl-filled" /></template>
