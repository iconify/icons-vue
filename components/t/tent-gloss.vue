<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfpzj2bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfpzj2bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tent-gloss" /></template>
