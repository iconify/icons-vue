<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_soae0bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_soae0bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mobx-state-tree" /></template>
