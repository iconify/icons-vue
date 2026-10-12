<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voz3i-6tt.css';
import '../../css/q/q2snesbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voz3i-6tt"/><path class="q2snesbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-sparkles-filled" /></template>
