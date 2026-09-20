<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnalrkbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bnalrkbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:shipping-box-2-solid" /></template>
