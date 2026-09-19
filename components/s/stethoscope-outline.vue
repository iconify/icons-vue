<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ews_agbzg.css';
import '../../css/q/q869ue7ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ews_agbzg"/><path clip-rule="evenodd" class="q869ue7ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:stethoscope-outline" /></template>
