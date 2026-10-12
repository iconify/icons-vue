<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdei6-b8p.css';
import '../../css/s/sdpl1vxew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdei6-b8p"/><path class="sdpl1vxew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-lock-filled" /></template>
