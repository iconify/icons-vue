<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjlsc6boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjlsc6boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangle-alert-fill" /></template>
