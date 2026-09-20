<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3yci9bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3yci9bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:overleaf" /></template>
