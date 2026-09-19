<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9yfjzbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s9yfjzbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sofa-filled" /></template>
