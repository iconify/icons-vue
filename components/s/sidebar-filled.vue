<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajhn5acdw.css';
import '../../css/o/occ68iv3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajhn5acdw"/><path class="occ68iv3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sidebar-filled" /></template>
