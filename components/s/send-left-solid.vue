<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg0mhxhmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kg0mhxhmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:send-left-solid" /></template>
