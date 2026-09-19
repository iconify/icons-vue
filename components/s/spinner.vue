<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aipr_bcuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aipr_bcuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:spinner" /></template>
