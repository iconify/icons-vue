<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zotrfkt_o.css';
import '../../css/f/fp8qfjbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zotrfkt_o"/><path clip-rule="evenodd" class="fp8qfjbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-b-filled" /></template>
