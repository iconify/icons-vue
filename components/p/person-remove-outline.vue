<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w53752bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w53752bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:person-remove-outline" /></template>
