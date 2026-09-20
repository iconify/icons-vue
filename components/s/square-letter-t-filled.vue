<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynyb3aclq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynyb3aclq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-t-filled" /></template>
