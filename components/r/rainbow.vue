<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5oqb4b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-7};
const content = `<path class="o5oqb4b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:rainbow" /></template>
