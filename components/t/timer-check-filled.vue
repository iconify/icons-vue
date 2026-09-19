<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n97kby4rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n97kby4rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:timer-check-filled" /></template>
