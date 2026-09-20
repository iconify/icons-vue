<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbi7zsbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbi7zsbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:usb" /></template>
