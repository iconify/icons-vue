<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vya2bnlvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vya2bnlvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:radar4-filled" /></template>
