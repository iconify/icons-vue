<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq74-9bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wq74-9bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:textmate" /></template>
