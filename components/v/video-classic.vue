<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfiyrjvdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfiyrjvdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-classic" /></template>
