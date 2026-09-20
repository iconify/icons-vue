<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7pkxcccs.css';
import '../../css/k/k4rjlac_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7pkxcccs"/><path class="k4rjlac_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sign-out-squre-duotone-line" /></template>
