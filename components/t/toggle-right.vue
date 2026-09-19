<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vooho20fj.css';
import '../../css/v/vi0k319by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vooho20fj"/><path class="vi0k319by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:toggle-right" /></template>
