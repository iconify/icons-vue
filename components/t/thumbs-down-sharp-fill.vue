<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl6u6_7vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl6u6_7vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thumbs-down-sharp-fill" /></template>
