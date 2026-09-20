<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwt-edbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwt-edbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mdn-web-docs" /></template>
