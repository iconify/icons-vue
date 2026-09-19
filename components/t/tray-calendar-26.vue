<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orgn1ubrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="orgn1ubrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tray-calendar-26" /></template>
