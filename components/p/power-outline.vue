<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoj597b8y.css';
import '../../css/l/lb_j2db8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoj597b8y"/><path class="lb_j2db8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:power-outline" /></template>
