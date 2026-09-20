<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn_3pob7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn_3pob7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:minus-square-fill" /></template>
