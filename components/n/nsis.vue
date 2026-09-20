<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n157im9qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n157im9qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nsis" /></template>
