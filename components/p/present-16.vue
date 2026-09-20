<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpgq7rm-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bpgq7rm-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:present-16" /></template>
