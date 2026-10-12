<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuf07w3fy.css';
import '../../css/j/jnfkx1eag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zuf07w3fy"/><path class="jnfkx1eag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pizza-filled" /></template>
