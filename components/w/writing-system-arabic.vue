<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiu31ywbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiu31ywbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:writing-system-arabic" /></template>
