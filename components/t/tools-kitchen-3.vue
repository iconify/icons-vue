<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rudvr6l0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rudvr6l0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tools-kitchen-3" /></template>
