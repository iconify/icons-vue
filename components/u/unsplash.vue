<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acbz_02fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acbz_02fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:unsplash" /></template>
