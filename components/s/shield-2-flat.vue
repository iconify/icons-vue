<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/int4-7b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="int4-7b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:shield-2-flat" /></template>
