<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk0gphdku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk0gphdku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:slack" /></template>
