<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz3basbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vz3basbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sparks-alt" /></template>
