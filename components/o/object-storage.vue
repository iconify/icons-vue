<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvk3n9b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvk3n9b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:object-storage" /></template>
