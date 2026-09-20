<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azosf2fdp.css';
import '../../css/f/folb2v_pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azosf2fdp"/><path clip-rule="evenodd" class="folb2v_pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:whatsapp-line" /></template>
