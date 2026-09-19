<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_et0-cib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_et0-cib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:mobile-vibration" /></template>
