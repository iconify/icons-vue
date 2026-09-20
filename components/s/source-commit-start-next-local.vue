<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6e-3dwpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6e-3dwpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:source-commit-start-next-local" /></template>
