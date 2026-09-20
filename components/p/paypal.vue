<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw3ucqbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw3ucqbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paypal" /></template>
