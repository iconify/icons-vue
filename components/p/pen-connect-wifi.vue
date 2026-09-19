<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhw5u9d6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhw5u9d6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pen-connect-wifi" /></template>
