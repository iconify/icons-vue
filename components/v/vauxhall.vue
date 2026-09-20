<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crvcl9i5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crvcl9i5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vauxhall" /></template>
