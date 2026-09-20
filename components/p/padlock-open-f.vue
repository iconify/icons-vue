<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhor97rim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="zhor97rim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:padlock-open-f" /></template>
