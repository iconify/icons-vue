<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcxv81l_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jcxv81l_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-division-square-fill" /></template>
