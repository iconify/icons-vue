<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuww48bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuww48bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sign-in-24" /></template>
