<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izgpe9bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="izgpe9bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:playlist2" /></template>
