<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owcl52bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owcl52bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-cancel" /></template>
