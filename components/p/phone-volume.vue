<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gky-n2bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="gky-n2bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:phone-volume" /></template>
