<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do7mjdbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="do7mjdbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:vials" /></template>
