<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbiunetgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbiunetgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mathematics-filled" /></template>
