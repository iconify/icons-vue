<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbga4bbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbga4bbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-many-to-zero-or-one" /></template>
