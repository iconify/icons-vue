<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcl7_1caz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcl7_1caz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf" /></template>
