<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jys00cbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jys00cbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-right-dashed-filled" /></template>
