<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpzeqkffn.css';
import '../../css/m/mzf3t7bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gpzeqkffn"/><path class="mzf3t7bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-search-filled" /></template>
