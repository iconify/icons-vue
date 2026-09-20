<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvca0tbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvca0tbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pail-remove" /></template>
