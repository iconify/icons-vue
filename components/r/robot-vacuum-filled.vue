<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf-5ik2ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lf-5ik2ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:robot-vacuum-filled" /></template>
