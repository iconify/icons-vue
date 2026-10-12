<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6567db_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6567db_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:vector-square-filled" /></template>
