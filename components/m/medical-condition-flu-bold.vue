<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg2knfbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg2knfbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:medical-condition-flu-bold" /></template>
