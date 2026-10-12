<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw0jtkbfd.css';
import '../../css/p/prq88gola.css';
import '../../css/z/zy5m7gbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw0jtkbfd"/><path class="prq88gola"/><path class="zy5m7gbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-stack-filled" /></template>
