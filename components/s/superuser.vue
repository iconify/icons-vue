<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpape142n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpape142n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:superuser" /></template>
