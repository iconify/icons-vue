<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jij--tp9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jij--tp9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mickeymouse-fill" /></template>
