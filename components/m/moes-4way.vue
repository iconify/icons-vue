<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jabs6t4yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jabs6t4yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:moes-4way" /></template>
