<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn_uedbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xn_uedbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:scan-filled" /></template>
