<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si6y8idcw.css';
import '../../css/w/w8iuawbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si6y8idcw"/><path clip-rule="evenodd" class="w8iuawbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-bold" /></template>
