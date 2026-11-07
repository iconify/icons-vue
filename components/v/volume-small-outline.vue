<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t88j5zbtr.css';
import '../../css/l/ls3hpxbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t88j5zbtr"/><path class="ls3hpxbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volume-small-outline" /></template>
