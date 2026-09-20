<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lznnucceq.css';
import '../../css/m/muuvzwbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lznnucceq"/><path class="muuvzwbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-split-duotone" /></template>
