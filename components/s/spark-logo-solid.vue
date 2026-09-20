<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4mxx4jim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e4mxx4jim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:spark-logo-solid" /></template>
