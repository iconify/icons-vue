<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyo_zsbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="zyo_zsbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:searchfolder" /></template>
