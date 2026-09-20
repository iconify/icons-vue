<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-pkev7bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-pkev7bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:namecheap" /></template>
