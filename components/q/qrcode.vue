<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyx5u8btq.css';
import '../../css/d/d-beombpy.css';
import '../../css/y/ygr8_mw8f.css';
import '../../css/m/myuqn2b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kyx5u8btq"/><path class="d-beombpy"/><path class="ygr8_mw8f"/><path class="myuqn2b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:qrcode" /></template>
