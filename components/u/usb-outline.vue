<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9bko0nfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9bko0nfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:usb-outline" /></template>
