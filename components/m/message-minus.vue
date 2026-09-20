<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de8w2obig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de8w2obig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-minus" /></template>
