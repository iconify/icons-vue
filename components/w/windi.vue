<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkvh3ejfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":512};
const content = `<path class="lkvh3ejfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:windi" /></template>
