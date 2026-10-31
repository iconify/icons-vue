<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu-yry1nz.css';
import '../../css/x/x92eckbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tu-yry1nz"/><path clip-rule="evenodd" class="x92eckbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-r-filled" /></template>
