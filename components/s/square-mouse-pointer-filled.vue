<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd3tyqb5z.css';
import '../../css/r/rvqm-4muf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd3tyqb5z"/><path class="rvqm-4muf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-mouse-pointer-filled" /></template>
