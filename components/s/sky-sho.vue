<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml-dwsbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml-dwsbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sky-sho" /></template>
