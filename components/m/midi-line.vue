<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-x9pmb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-x9pmb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:midi-line" /></template>
