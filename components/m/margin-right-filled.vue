<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy3u8dwwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy3u8dwwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:margin-right-filled" /></template>
