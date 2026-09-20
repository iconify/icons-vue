<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irpm2abtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="irpm2abtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:phone-square-alt" /></template>
