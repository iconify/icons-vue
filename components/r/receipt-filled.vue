<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz_8thepw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sz_8thepw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receipt-filled" /></template>
