<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojym71bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ojym71bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:menu" /></template>
