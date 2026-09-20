<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3kpo5i1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3kpo5i1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:mars" /></template>
