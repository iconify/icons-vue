<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw6oiua1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw6oiua1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roomsoffice" /></template>
