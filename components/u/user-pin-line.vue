<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps1e0_brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps1e0_brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-pin-line" /></template>
