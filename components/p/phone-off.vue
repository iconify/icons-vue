<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haq5j_n4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haq5j_n4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-off" /></template>
