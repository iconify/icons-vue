<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o72-pkb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o72-pkb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:puzzle-filled" /></template>
