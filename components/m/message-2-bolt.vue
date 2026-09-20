<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe1k7lb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe1k7lb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-bolt" /></template>
