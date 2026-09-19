<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is3xbuo4a.css';
import '../../css/a/a6vuirsuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is3xbuo4a"/><path class="a6vuirsuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:trash-x" /></template>
