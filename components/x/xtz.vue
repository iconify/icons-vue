<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q--tgpq3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q--tgpq3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xtz" /></template>
