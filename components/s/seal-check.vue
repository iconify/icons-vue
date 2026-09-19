<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6-_lmbbc.css';
import '../../css/x/xvqdfg4fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6-_lmbbc"/><path class="xvqdfg4fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:seal-check" /></template>
