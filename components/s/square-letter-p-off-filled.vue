<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs_nhrb3i.css';
import '../../css/v/vx68g0b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs_nhrb3i"/><path class="vx68g0b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-p-off-filled" /></template>
