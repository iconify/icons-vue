<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmhvf_b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nmhvf_b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:test-tube-solid" /></template>
