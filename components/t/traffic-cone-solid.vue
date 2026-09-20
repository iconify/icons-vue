<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb7tmr36t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mb7tmr36t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:traffic-cone-solid" /></template>
