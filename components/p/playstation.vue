<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oly_4rbgm.css';
import '../../css/s/steyv6bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oly_4rbgm"/><path class="steyv6bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:playstation" /></template>
