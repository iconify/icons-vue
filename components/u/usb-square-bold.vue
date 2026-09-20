<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzw00zbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dzw00zbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:usb-square-bold" /></template>
