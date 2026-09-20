<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emdtvd_xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emdtvd_xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rolling-pin-broken" /></template>
