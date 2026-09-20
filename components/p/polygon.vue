<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu7w6xbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qu7w6xbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:polygon" /></template>
