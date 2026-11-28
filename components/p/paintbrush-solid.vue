<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sck_21-ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sck_21-ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:paintbrush-solid" /></template>
