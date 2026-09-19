<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f35rpc67l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f35rpc67l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:unlink-sharp" /></template>
