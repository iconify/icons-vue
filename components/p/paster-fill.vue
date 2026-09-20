<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt-bdj62o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt-bdj62o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paster-fill" /></template>
