<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzw309b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gzw309b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:mouse-alt-solid" /></template>
