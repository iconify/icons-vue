<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t46oz2bvl.css';
import '../../css/j/j4v_2dxrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t46oz2bvl"/><path clip-rule="evenodd" class="j4v_2dxrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-stop-filled" /></template>
