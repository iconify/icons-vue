<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djl73n95t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djl73n95t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tea-solid" /></template>
