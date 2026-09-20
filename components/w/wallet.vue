<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpho4wbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpho4wbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:wallet" /></template>
