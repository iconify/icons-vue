<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgxo6jbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rgxo6jbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:synthesizer-24" /></template>
