<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_r4qxznw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_r4qxznw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-outline" /></template>
