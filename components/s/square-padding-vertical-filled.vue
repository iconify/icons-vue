<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2q6z77ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2q6z77ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-padding-vertical-filled" /></template>
