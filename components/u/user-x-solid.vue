<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkks6l3vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkks6l3vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:user-x-solid" /></template>
