<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka3v7gmwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="ka3v7gmwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:padlock-open" /></template>
