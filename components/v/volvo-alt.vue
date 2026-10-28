<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma_gifbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma_gifbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:volvo-alt" /></template>
