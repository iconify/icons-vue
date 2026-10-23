<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsh9tzb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsh9tzb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:metronome" /></template>
