<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvj7bnbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vvj7bnbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:wireguard" /></template>
