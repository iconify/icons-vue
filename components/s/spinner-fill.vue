<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv6qmsbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv6qmsbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:spinner-fill" /></template>
