<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o03swkghw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o03swkghw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:share-2-fill" /></template>
