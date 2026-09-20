<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyxb2y9tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vyxb2y9tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:op" /></template>
