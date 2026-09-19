<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3-2mab7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3-2mab7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:push-pin-outlined" /></template>
