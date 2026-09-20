<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th2-4rb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="th2-4rb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mask-happly-bold" /></template>
