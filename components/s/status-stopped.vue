<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnc9k-r_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="gnc9k-r_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:status-stopped" /></template>
