<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh_6zjivc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh_6zjivc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:qrcode" /></template>
