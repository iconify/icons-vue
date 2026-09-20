<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzf4xnbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6,"top":-1};
const content = `<path class="gzf4xnbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:watch-f" /></template>
