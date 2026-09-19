<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt3t_vb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt3t_vb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-lines" /></template>
