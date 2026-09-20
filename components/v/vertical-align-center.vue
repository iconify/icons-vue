<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh-_msqeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh-_msqeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:vertical-align-center" /></template>
