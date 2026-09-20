<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhmb09bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhmb09bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sun-filled" /></template>
