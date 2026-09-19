<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_u_3ebpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_u_3ebpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:shield-outline" /></template>
