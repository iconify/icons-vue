<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf_oem-1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf_oem-1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-stop" /></template>
