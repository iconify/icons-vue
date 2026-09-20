<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krh13ab-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krh13ab-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-remove" /></template>
