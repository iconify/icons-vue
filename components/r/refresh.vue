<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx76tdlhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx76tdlhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:refresh" /></template>
