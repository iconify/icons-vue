<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks9868eyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ks9868eyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:presentation2" /></template>
