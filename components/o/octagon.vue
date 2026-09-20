<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov4tu3wkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov4tu3wkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:octagon" /></template>
