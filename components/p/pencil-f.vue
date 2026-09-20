<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyo9mrvne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2.5};
const content = `<path class="fyo9mrvne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:pencil-f" /></template>
