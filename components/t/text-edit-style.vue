<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un5ari44h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un5ari44h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-edit-style" /></template>
