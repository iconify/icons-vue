<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq9-uch7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eq9-uch7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:perfume-outline" /></template>
