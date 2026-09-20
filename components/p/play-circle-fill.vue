<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m49rw4yqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m49rw4yqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:play-circle-fill" /></template>
