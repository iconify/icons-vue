<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooe76jbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ooe76jbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-cane" /></template>
