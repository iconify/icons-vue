<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq56j2bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nq56j2bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tornado" /></template>
