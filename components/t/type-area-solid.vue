<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2ew_ta5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o2ew_ta5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:type-area-solid" /></template>
