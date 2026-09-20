<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8mozdbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8mozdbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-zero-or-one-to-one" /></template>
