<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh0fupbic.css';
import '../../css/u/u9p7tmx1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lh0fupbic"/><path class="u9p7tmx1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:t-shirt-bold-duotone" /></template>
