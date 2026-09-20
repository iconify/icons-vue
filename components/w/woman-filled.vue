<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_imh8p1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_imh8p1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:woman-filled" /></template>
