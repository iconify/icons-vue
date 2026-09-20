<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_8xdqbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_8xdqbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:restart-circle-bold" /></template>
