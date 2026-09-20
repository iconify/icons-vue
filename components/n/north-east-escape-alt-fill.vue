<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4gxo_bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k4gxo_bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-east-escape-alt-fill" /></template>
