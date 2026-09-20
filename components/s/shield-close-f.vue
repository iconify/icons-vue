<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlv_0xbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="zlv_0xbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:shield-close-f" /></template>
