<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs47u9j4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs47u9j4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pen-brush-filled" /></template>
