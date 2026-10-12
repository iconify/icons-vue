<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo1yws-pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo1yws-pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:signpost-big-filled" /></template>
