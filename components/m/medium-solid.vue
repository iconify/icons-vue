<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-sk7-3fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k-sk7-3fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:medium-solid" /></template>
