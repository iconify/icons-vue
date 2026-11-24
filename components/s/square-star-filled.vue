<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2cq6phge.css';
import '../../css/b/bpmeeqg8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2cq6phge"/><path clip-rule="evenodd" class="bpmeeqg8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-star-filled" /></template>
