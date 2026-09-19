<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twidg77uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twidg77uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pause-circle-filled" /></template>
