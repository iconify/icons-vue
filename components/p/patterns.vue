<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqn7c3blc.css';
import '../../css/b/bfe0-acgo.css';
import '../../css/u/uaq5afiat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="vqn7c3blc"/><path class="bfe0-acgo"/><circle class="uaq5afiat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:patterns" /></template>
