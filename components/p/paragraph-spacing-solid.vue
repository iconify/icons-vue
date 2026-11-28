<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxxo35b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxxo35b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:paragraph-spacing-solid" /></template>
