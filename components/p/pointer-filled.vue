<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqb4ezbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqb4ezbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-filled" /></template>
