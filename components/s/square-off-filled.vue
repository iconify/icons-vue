<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uye2wsfpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uye2wsfpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-off-filled" /></template>
