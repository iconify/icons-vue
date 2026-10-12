<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg1p4x-oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fg1p4x-oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:snail-filled" /></template>
