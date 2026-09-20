<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh8c8_b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eh8c8_b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:om" /></template>
