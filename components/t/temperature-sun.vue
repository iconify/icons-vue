<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae1i43b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae1i43b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:temperature-sun" /></template>
