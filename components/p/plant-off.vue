<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9s5or3lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9s5or3lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plant-off" /></template>
