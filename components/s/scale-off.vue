<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aakw6q4ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aakw6q4ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:scale-off" /></template>
