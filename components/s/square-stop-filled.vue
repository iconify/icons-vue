<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qahyg6byo.css';
import '../../css/z/zu_sz4rou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qahyg6byo"/><path clip-rule="evenodd" class="zu_sz4rou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-stop-filled" /></template>
