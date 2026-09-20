<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flkqr0bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flkqr0bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:money3-filled" /></template>
