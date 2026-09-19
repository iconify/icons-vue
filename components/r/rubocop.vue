<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebbz1ybvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":433,"height":512};
const content = `<path class="ebbz1ybvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:rubocop" /></template>
