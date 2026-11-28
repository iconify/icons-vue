<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cep8l2b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cep8l2b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:toolbox-check" /></template>
