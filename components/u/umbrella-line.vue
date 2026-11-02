<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2hpfpjcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2hpfpjcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:umbrella-line" /></template>
