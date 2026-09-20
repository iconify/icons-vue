<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at9xv_bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at9xv_bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:qrcode-remove" /></template>
