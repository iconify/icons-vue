<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiv_d-bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiv_d-bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roomsbalcony" /></template>
