<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqvr3s70x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqvr3s70x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-bottom-left-outline" /></template>
