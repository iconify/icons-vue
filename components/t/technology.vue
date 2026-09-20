<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgujrohyl.css';
import '../../css/b/b07penbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgujrohyl"/><path class="b07penbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:technology" /></template>
