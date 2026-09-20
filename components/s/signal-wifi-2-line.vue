<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upqvygbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upqvygbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-wifi-2-line" /></template>
