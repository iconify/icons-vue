<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwv8wbscl.css';
import '../../css/m/m7s0i2b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwv8wbscl"/><path class="m7s0i2b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:space-24" /></template>
