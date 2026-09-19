<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz9twfbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":474,"height":512};
const content = `<path class="wz9twfbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:spacengine" /></template>
