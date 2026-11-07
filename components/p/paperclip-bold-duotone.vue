<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2bnn7ohn.css';
import '../../css/j/jkdbh9btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k2bnn7ohn"/><path class="jkdbh9btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-bold-duotone" /></template>
