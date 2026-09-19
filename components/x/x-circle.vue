<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3-5554gl.css';
import '../../css/l/lmgxn5bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3-5554gl"/><path class="lmgxn5bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:x-circle" /></template>
