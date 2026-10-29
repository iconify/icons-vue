<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt6ep9b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt6ep9b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:share-2" /></template>
