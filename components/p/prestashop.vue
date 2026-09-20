<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av-ff1z_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av-ff1z_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:prestashop" /></template>
