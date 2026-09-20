<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekj4x8z7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekj4x8z7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-pin" /></template>
