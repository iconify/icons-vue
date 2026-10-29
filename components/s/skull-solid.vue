<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp0rrubaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp0rrubaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:skull-solid" /></template>
