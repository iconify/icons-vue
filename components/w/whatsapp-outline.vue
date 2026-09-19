<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2llag50o.css';
import '../../css/l/lq4vgwbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2llag50o"/><path clip-rule="evenodd" class="lq4vgwbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:whatsapp-outline" /></template>
