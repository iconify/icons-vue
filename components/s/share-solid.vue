<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o05ysfamp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o05ysfamp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:share-solid" /></template>
