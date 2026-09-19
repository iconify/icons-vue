<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu9h76b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qu9h76b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:window-maximize" /></template>
