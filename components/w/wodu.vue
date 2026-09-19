<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb2lmabfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pb2lmabfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:wodu" /></template>
