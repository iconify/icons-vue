<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcm9-cbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcm9-cbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:map-pin-off-solid" /></template>
