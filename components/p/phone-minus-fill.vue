<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zamd5-oru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zamd5-oru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:phone-minus-fill" /></template>
