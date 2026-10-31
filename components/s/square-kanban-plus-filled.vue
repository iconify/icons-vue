<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu0if9b0f.css';
import '../../css/q/qb2gh7q5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hu0if9b0f"/><path class="qb2gh7q5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-kanban-plus-filled" /></template>
