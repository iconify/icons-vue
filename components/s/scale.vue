<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-jc9896g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-jc9896g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:scale" /></template>
