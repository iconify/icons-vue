<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdrq5fk-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hdrq5fk-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tennis" /></template>
