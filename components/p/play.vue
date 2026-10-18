<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac0-4ubcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac0-4ubcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:play" /></template>
