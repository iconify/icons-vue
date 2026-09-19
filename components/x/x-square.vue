<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jor-usn7v.css';
import '../../css/y/y3-5554gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jor-usn7v"/><path class="y3-5554gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:x-square" /></template>
