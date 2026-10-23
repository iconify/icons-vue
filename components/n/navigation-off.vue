<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzze5nbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzze5nbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:navigation-off" /></template>
