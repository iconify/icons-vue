<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1se8tbgo.css';
import '../../css/q/qje49sx-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1se8tbgo"/><path class="qje49sx-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tablet-smartphone-filled" /></template>
