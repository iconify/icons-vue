<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acoyk8bzs.css';
import '../../css/x/xe4n45bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acoyk8bzs"/><path clip-rule="evenodd" class="xe4n45bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-cog-filled" /></template>
