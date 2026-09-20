<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyl-0kw5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyl-0kw5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pet-friendly-hotel-solid" /></template>
