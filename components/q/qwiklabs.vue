<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgjwnkjpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgjwnkjpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:qwiklabs" /></template>
