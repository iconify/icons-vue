<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6d5uggdo.css';
import '../../css/c/cuzgrrbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6d5uggdo"/><path class="cuzgrrbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:phone-call" /></template>
