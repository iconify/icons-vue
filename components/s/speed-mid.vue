<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3p2f3b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c3p2f3b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:speed-mid" /></template>
