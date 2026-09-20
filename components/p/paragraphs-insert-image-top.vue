<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-mhshb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o-mhshb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:paragraphs-insert-image-top" /></template>
