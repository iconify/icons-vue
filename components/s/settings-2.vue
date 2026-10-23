<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot0oobcet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot0oobcet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:settings-2" /></template>
