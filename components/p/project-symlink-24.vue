<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsjs4_b4y.css';
import '../../css/c/ckbg2-b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsjs4_b4y"/><path class="ckbg2-b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:project-symlink-24" /></template>
