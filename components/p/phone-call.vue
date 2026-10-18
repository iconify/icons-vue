<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6cbdjb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6cbdjb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:phone-call" /></template>
