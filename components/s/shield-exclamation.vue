<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aexe18bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aexe18bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-exclamation" /></template>
