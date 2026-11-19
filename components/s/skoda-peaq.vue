<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay1d6pr1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay1d6pr1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:skoda-peaq" /></template>
