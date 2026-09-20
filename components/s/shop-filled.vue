<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwrxwtbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwrxwtbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shop-filled" /></template>
