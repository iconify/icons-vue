<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxkm2urco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxkm2urco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:password-lock" /></template>
