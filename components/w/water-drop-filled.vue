<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf_hh-lha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tf_hh-lha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:water-drop-filled" /></template>
