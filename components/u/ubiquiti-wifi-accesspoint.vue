<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynkwuebdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynkwuebdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubiquiti-wifi-accesspoint" /></template>
