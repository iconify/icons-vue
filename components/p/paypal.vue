<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfoz52bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pfoz52bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:paypal" /></template>
