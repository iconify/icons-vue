<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kge_lwb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kge_lwb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skateboard-line" /></template>
