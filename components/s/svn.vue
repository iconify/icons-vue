<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndxyiq8pj.css';
import '../../css/l/lyhf8fbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":24};
const content = `<path class="ndxyiq8pj"/><path class="lyhf8fbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:svn" /></template>
