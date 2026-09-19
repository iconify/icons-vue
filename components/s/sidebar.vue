<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w697-jb9w.css';
import '../../css/o/occ68iv3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w697-jb9w"/><path class="occ68iv3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sidebar" /></template>
