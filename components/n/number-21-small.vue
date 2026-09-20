<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6bg_5m0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6bg_5m0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-21-small" /></template>
