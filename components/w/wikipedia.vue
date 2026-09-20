<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r04ouyb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="r04ouyb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:wikipedia" /></template>
