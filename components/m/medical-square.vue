<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkuh8za8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkuh8za8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:medical-square" /></template>
