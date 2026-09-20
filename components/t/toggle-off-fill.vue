<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxyat7jji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxyat7jji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:toggle-off-fill" /></template>
