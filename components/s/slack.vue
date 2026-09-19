<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqt8a942q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqt8a942q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:slack" /></template>
