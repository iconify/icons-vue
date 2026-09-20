<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek0xau4pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek0xau4pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:windowsxp" /></template>
