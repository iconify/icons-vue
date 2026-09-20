<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgm3tebms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgm3tebms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rabbitmq" /></template>
