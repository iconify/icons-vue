<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlrw65cjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlrw65cjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:metabase" /></template>
