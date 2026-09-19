<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw4z6cbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw4z6cbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pathe" /></template>
