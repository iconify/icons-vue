<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghswe8lyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghswe8lyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:qiita" /></template>
