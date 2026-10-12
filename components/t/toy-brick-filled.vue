<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aexrj4beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aexrj4beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:toy-brick-filled" /></template>
