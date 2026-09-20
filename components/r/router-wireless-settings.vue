<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe8acnbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe8acnbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:router-wireless-settings" /></template>
