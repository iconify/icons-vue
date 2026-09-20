<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1d55jbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1d55jbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:remove-delete-sign-bold" /></template>
