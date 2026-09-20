<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy1nasb1l.css';
import '../../css/f/fpys2ac3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy1nasb1l"/><path class="fpys2ac3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:xampp" /></template>
