<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vli4yubzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vli4yubzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:thumbs-up" /></template>
