<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcgrw9bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tcgrw9bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:wlan-strength-3" /></template>
