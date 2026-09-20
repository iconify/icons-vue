<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5maegvba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5maegvba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:medical-search-diagnosis-solid" /></template>
