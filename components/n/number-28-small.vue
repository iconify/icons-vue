<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtdoon55r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtdoon55r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-28-small" /></template>
