<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a20z3n5cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a20z3n5cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:more-4-fill" /></template>
