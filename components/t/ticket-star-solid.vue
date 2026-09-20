<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl_fgnk_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sl_fgnk_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ticket-star-solid" /></template>
