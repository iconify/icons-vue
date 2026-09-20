<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uggdc9ofk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uggdc9ofk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-y-plus-y" /></template>
