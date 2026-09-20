<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxt8g5bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxt8g5bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:webauthn" /></template>
