<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkk3_lgdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkk3_lgdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-hands-filled" /></template>
