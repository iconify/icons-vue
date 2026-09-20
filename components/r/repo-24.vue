<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diaqm204w.css';
import '../../css/j/juknf3fay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="diaqm204w"/><path class="juknf3fay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-24" /></template>
