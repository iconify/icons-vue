<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry2mczbpi.css';
import '../../css/j/jor-usn7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b ry2mczbpi"/><path class="b jor-usn7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pencil-square" /></template>
